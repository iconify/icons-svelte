<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5d43wbfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="p5d43wbfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:recording-tape-bubble-circle-remix" {...props}></Icon>
