<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hza2asblm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":480,"height":496};
const content = `<path class="hza2asblm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:promo" {...props}></Icon>
