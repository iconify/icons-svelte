<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdy94ccpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="rdy94ccpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:and" {...props}></Icon>
