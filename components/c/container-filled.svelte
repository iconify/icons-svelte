<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3k0r13bp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j3k0r13bp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:container-filled" {...props}></Icon>
