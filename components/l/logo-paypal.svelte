<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v8sacuuou.css';
import '../../css/y/yusbh7bbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v8sacuuou"/><path class="yusbh7bbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:logo-paypal" {...props}></Icon>
