<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ab118kbzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ab118kbzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:circle-arrow-right" {...props}></Icon>
