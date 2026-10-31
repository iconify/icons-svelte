<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3mewwtws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i3mewwtws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:hot-air-balloon-filled" {...props}></Icon>
