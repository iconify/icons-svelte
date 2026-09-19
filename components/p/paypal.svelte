<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjcugmbto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="cjcugmbto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:paypal" {...props}></Icon>
