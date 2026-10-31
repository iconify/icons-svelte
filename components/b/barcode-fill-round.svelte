<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4l39xbyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f4l39xbyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:barcode-fill-round" {...props}></Icon>
