<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4h9kcc8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="o4h9kcc8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:new-folder-remix" {...props}></Icon>
