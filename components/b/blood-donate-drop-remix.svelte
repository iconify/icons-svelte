<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0l9xsbco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="o0l9xsbco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:blood-donate-drop-remix" {...props}></Icon>
