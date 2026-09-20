<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j04tt7qvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="j04tt7qvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:ai-prompt-spark-solid" {...props}></Icon>
