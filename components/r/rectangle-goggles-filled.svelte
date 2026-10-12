<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tloxr4bfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tloxr4bfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:rectangle-goggles-filled" {...props}></Icon>
