<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j36ac2b3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j36ac2b3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:message-square-warning-gloss" {...props}></Icon>
