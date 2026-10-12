<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kip_gc83p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kip_gc83p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:book-up-filled" {...props}></Icon>
