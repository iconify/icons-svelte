<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-ardxbzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="z-ardxbzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:input-box-remix" {...props}></Icon>
