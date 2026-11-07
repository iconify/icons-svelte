<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nw3wxe0oi.css';
import '../../css/f/fnwhem6it.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nw3wxe0oi"/><path class="fnwhem6it"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:notes-bold-duotone" {...props}></Icon>
