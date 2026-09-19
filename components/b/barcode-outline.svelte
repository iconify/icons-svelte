<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lm54_4bbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lm54_4bbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:barcode-outline" {...props}></Icon>
