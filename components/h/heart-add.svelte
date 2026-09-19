<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unnj-gbei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="unnj-gbei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:heart-add" {...props}></Icon>
