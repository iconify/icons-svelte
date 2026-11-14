<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdj4t8jqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qdj4t8jqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:call" {...props}></Icon>
