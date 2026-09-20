<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ii82hnrhg.css';
import '../../css/l/lzpmdx6fy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path class="ii82hnrhg"/><path class="lzpmdx6fy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:cloud-rain" {...props}></Icon>
