<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp03et8ui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bp03et8ui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:plane-up" {...props}></Icon>
