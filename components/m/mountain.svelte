<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cg4jzmbzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cg4jzmbzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:mountain" {...props}></Icon>
