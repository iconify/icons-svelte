<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pol0z9bwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pol0z9bwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:copilot-warning" {...props}></Icon>
