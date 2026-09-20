<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ac7e6ph4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ac7e6ph4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:manual-book-remix" {...props}></Icon>
