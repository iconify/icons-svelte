<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0ca_zb6s.css';
import '../../css/b/b4v04k7yk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b0ca_zb6s"/><path clip-rule="evenodd" class="b4v04k7yk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:brain-cog-filled" {...props}></Icon>
