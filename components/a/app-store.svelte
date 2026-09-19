<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6vyf9bfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":464};
const content = `<path class="z6vyf9bfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:app-store" {...props}></Icon>
