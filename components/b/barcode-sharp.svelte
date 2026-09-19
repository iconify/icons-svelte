<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vk0dibbez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vk0dibbez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:barcode-sharp" {...props}></Icon>
