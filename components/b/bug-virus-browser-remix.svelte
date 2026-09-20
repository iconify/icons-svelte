<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-uxht4zc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="h-uxht4zc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:bug-virus-browser-remix" {...props}></Icon>
