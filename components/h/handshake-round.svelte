<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eekql3xep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eekql3xep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:handshake-round" {...props}></Icon>
