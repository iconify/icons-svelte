<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv2u-nbua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sv2u-nbua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:bold-q" {...props}></Icon>
