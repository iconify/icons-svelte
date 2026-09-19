<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/waq7f_0of.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="waq7f_0of"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:cedi-sign" {...props}></Icon>
