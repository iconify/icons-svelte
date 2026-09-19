<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0a38yrne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="m0a38yrne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:magento" {...props}></Icon>
