<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3-qswb0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e3-qswb0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:circle-letter-s-filled" {...props}></Icon>
