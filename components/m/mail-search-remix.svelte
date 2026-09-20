<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7q77thdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="j7q77thdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:mail-search-remix" {...props}></Icon>
