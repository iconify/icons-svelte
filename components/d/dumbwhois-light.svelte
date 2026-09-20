<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nokeo3bua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nokeo3bua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dumbwhois-light" {...props}></Icon>
