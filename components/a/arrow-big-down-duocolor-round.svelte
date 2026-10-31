<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgvk0vbnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pgvk0vbnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-big-down-duocolor-round" {...props}></Icon>
