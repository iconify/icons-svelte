<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6eh32bir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e6eh32bir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:barcode-20-bold" {...props}></Icon>
