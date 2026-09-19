<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnqn87_3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1792};
const content = `<path class="xnqn87_3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:mic" {...props}></Icon>
