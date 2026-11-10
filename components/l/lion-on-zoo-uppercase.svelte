<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ongxg380j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ongxg380j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:lion-on-zoo-uppercase" {...props}></Icon>
