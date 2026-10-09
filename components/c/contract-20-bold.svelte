<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gx0wpfbrz.css';
import '../../css/y/yc_qcr2ri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gx0wpfbrz"/><path class="yc_qcr2ri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:contract-20-bold" {...props}></Icon>
