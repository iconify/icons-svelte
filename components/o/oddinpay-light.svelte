<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e910xyhfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":35,"height":35};
const content = `<path class="e910xyhfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:oddinpay-light" {...props}></Icon>
