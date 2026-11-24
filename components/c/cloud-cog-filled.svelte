<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0j5jlbnz.css';
import '../../css/l/lhpluxdub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z0j5jlbnz"/><path class="lhpluxdub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cloud-cog-filled" {...props}></Icon>
