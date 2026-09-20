<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxx9ecuqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fxx9ecuqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:cash-register-solid" {...props}></Icon>
