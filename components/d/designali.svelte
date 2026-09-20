<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnx5jt5yo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1440,"height":1440};
const content = `<path class="rnx5jt5yo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:designali" {...props}></Icon>
