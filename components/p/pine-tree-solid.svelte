<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b__9bgb9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="b__9bgb9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:pine-tree-solid" {...props}></Icon>
