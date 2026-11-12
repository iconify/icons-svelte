<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdfl41b6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kdfl41b6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bknd-light" {...props}></Icon>
