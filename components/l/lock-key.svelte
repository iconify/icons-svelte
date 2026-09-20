<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8206dvpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="i8206dvpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:lock-key" {...props}></Icon>
