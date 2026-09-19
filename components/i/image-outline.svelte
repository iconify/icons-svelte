<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhrxheaqf.css';
import '../../css/p/pq_3tfnsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lhrxheaqf"/><path clip-rule="evenodd" class="pq_3tfnsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:image-outline" {...props}></Icon>
