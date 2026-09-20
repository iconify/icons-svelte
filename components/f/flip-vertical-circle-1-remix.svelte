<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8ec9gpjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="a8ec9gpjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:flip-vertical-circle-1-remix" {...props}></Icon>
