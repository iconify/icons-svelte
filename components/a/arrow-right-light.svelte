<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7z-gpbab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m7z-gpbab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:arrow-right-light" {...props}></Icon>
