<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn7xlvr2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="xn7xlvr2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:cctv" {...props}></Icon>
