<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j23q22bdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="j23q22bdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:recording-tape-bubble-circle-remix" {...props}></Icon>
