<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7lu9-m2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y7lu9-m2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:barcode-fill" {...props}></Icon>
