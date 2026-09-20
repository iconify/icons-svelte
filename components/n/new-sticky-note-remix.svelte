<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1ic187jv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="y1ic187jv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:new-sticky-note-remix" {...props}></Icon>
