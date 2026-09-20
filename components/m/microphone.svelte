<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ai8j3lypx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ai8j3lypx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:microphone" {...props}></Icon>
