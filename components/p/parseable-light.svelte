<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ioq9ntycb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ioq9ntycb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:parseable-light" {...props}></Icon>
