<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/syb3c432m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="syb3c432m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:cam-track" {...props}></Icon>
