<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cf2-1wf3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cf2-1wf3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:popcorn-solid" {...props}></Icon>
