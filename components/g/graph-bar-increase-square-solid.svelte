<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4tmdyemy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="x4tmdyemy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:graph-bar-increase-square-solid" {...props}></Icon>
