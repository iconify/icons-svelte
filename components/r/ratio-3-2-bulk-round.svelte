<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jt3tfnmyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jt3tfnmyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:ratio-3-2-bulk-round" {...props}></Icon>
