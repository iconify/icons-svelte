<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-pi-2n5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="k-pi-2n5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:chevron-left-round" {...props}></Icon>
