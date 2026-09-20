<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jspn7gvku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jspn7gvku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:markdown-circle-programming-remix" {...props}></Icon>
