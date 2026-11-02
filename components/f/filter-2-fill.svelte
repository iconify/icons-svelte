<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r27q04b3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r27q04b3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:filter-2-fill" {...props}></Icon>
