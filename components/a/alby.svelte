<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xll1rbcfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xll1rbcfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:alby" {...props}></Icon>
