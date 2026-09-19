<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wezx3bbsv.css';
import '../../css/j/j14wpibjz.css';
import '../../css/w/wv5glxoac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wezx3bbsv"/><path class="j14wpibjz"/><path class="wv5glxoac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:compose" {...props}></Icon>
