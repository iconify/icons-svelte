<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0a5y4b5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p0a5y4b5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:barcode-line" {...props}></Icon>
