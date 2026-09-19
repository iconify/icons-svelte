<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mc7z9jb5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mc7z9jb5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cafe" {...props}></Icon>
