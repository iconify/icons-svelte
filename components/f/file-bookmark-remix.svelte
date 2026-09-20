<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u21wudb0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="u21wudb0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:file-bookmark-remix" {...props}></Icon>
