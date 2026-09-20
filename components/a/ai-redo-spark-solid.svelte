<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgfptlk-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mgfptlk-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:ai-redo-spark-solid" {...props}></Icon>
