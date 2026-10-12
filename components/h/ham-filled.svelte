<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8zqi2t4s.css';
import '../../css/x/x44at5b5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f8zqi2t4s"/><path clip-rule="evenodd" class="x44at5b5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:ham-filled" {...props}></Icon>
