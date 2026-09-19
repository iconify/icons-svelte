<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3ientf3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="q3ientf3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:mic-off-compact" {...props}></Icon>
