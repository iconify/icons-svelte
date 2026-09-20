<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3mtcrbur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="w3mtcrbur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:line-arrow-move-horizontal-remix" {...props}></Icon>
