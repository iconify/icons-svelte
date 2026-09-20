<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ah4pulxlj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ah4pulxlj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:like-1-remix" {...props}></Icon>
