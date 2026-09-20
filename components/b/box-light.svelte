<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fe46s0bzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fe46s0bzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:box-light" {...props}></Icon>
