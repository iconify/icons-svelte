<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fezhcwz_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":456,"height":488};
const content = `<path class="fezhcwz_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:paypal" {...props}></Icon>
