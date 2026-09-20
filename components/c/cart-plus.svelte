<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r82s_ibsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r82s_ibsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:cart-plus" {...props}></Icon>
