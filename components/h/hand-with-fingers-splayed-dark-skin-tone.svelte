<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yc8kfn0zy.css';
import '../../css/a/acwejz0_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="yc8kfn0zy"/><path class="acwejz0_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:hand-with-fingers-splayed-dark-skin-tone" {...props}></Icon>
