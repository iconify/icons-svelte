<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lg0lz9bfx.css';
import '../../css/y/y-np30t2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="lg0lz9bfx"/><path class="y-np30t2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bench-filled" {...props}></Icon>
