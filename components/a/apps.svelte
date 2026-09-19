<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7x0_fbqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l7x0_fbqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:apps" {...props}></Icon>
