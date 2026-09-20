<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ueb6e8bmp.css';
import '../../css/i/i0qqi58le.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ueb6e8bmp"/><path class="i0qqi58le"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:paste-ltr" {...props}></Icon>
