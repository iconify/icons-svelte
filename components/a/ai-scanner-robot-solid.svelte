<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dbijocc2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="dbijocc2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:ai-scanner-robot-solid" {...props}></Icon>
