<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwxb-w_rr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":14};
const content = `<path class="pwxb-w_rr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:dogecoin" {...props}></Icon>
