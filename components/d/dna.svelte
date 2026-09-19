<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kf0zdtb0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="kf0zdtb0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:dna" {...props}></Icon>
