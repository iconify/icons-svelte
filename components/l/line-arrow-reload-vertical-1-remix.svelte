<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-1t6y5ob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="f-1t6y5ob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:line-arrow-reload-vertical-1-remix" {...props}></Icon>
