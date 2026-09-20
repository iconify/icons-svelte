<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5rbfwb_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="e5rbfwb_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:city-hall-solid" {...props}></Icon>
