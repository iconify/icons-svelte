<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpy9_6bht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cpy9_6bht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:recording-tape-bubble-square-remix" {...props}></Icon>
