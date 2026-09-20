<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwyjs4bpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hwyjs4bpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:chess-king-remix" {...props}></Icon>
