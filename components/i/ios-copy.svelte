<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yg7wgbbdt.css';
import '../../css/e/efsxz5dnj.css';
import '../../css/r/rckjn3l5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yg7wgbbdt"/><path class="efsxz5dnj"/><path class="rckjn3l5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-copy" {...props}></Icon>
