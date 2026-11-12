<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dta1_oyxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dta1_oyxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fromkai" {...props}></Icon>
