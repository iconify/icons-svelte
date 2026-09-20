<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cg6_6qt2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="cg6_6qt2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:compsition-horizontal" {...props}></Icon>
