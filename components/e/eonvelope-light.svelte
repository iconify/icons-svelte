<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyemvd5bc.css';
import '../../css/v/vg0td9b8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jyemvd5bc"/><path class="vg0td9b8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:eonvelope-light" {...props}></Icon>
