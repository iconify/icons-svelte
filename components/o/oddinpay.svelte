<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uc87pduwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":35,"height":35};
const content = `<path class="uc87pduwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:oddinpay" {...props}></Icon>
