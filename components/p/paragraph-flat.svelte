<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rubbhlb5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rubbhlb5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:paragraph-flat" {...props}></Icon>
