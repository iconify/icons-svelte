<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ysr152bla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ysr152bla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:blood-drop-donation-remix" {...props}></Icon>
