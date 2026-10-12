<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1j12acbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q1j12acbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:map-pin-x-inside-filled" {...props}></Icon>
