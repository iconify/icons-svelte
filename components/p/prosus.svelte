<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxsavgw-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1416,"height":1591};
const content = `<path class="yxsavgw-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:prosus" {...props}></Icon>
