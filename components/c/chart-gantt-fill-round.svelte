<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0ds38bra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j0ds38bra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chart-gantt-fill-round" {...props}></Icon>
