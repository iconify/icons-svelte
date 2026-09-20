<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cblm0_q7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cblm0_q7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:quora" {...props}></Icon>
