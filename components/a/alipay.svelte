<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjjko4g0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="fjjko4g0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:alipay" {...props}></Icon>
