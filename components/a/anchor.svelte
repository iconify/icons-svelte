<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6ibt5u2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="j6ibt5u2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:anchor" {...props}></Icon>
