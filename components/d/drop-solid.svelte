<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utzl12bfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="utzl12bfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:drop-solid" {...props}></Icon>
