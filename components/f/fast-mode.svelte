<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwel8ob0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="cwel8ob0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:fast-mode" {...props}></Icon>
