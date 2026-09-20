<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b32f2rbcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="b32f2rbcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:film" {...props}></Icon>
