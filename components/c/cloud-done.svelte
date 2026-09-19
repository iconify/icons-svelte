<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tybfk_b5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tybfk_b5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:cloud-done" {...props}></Icon>
