<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggep1bc6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ggep1bc6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:book-medical-solid" {...props}></Icon>
