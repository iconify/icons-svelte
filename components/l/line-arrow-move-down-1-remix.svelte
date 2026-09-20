<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1_3gx95k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="n1_3gx95k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:line-arrow-move-down-1-remix" {...props}></Icon>
