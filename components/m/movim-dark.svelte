<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5-y7okkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g5-y7okkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:movim-dark" {...props}></Icon>
