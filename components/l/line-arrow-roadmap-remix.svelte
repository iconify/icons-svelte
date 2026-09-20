<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fa248iygj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fa248iygj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:line-arrow-roadmap-remix" {...props}></Icon>
