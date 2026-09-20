<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7mbenbgv.css';
import '../../css/j/j2bhf764p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e7mbenbgv"/><path class="j2bhf764p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:linux-fill" {...props}></Icon>
