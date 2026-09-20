<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5ww0trmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="a5ww0trmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:earth-1-remix" {...props}></Icon>
