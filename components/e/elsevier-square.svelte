<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x37jg-vpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="x37jg-vpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:elsevier-square" {...props}></Icon>
