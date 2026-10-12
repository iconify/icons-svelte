<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e08h97bpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e08h97bpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:popcorn-filled" {...props}></Icon>
