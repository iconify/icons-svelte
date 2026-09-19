<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cee5qpbfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cee5qpbfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:lens-convex" {...props}></Icon>
