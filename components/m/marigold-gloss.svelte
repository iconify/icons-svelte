<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urlwdxbzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="urlwdxbzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:marigold-gloss" {...props}></Icon>
