<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9gwph64c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":175,"height":735};
const content = `<path class="e9gwph64c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:1" {...props}></Icon>
