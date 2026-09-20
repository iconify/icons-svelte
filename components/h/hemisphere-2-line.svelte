<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lor3pcgfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lor3pcgfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hemisphere-2-line" {...props}></Icon>
