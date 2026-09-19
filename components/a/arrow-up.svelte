<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srcpcbb9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":304,"height":448};
const content = `<path class="srcpcbb9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:arrow-up" {...props}></Icon>
