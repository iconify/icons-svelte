<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zv4hdlb2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zv4hdlb2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:emulatorjs-light" {...props}></Icon>
