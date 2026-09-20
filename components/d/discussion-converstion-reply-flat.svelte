<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ows5bsbfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ows5bsbfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:discussion-converstion-reply-flat" {...props}></Icon>
