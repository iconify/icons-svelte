<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqyhhybfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jqyhhybfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:drill-fill" {...props}></Icon>
