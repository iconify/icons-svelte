<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfb4mjb7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rfb4mjb7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:image-size-select-large" {...props}></Icon>
