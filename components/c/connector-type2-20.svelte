<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_d-chbfv.css';
import '../../css/p/p48t35bio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r_d-chbfv"/><path class="p48t35bio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:connector-type2-20" {...props}></Icon>
