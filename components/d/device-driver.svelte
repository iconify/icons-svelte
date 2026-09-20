<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gc291pbfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="gc291pbfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:device-driver" {...props}></Icon>
