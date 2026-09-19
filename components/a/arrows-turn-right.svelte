<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8wyaabxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="d8wyaabxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:arrows-turn-right" {...props}></Icon>
