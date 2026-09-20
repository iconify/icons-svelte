<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t042mnbkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="t042mnbkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:recycle-1-remix" {...props}></Icon>
