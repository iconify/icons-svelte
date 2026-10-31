<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx6p4trgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lx6p4trgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:gabled-roof-with-fireplace-and-chimney" {...props}></Icon>
