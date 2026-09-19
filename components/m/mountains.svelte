<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrftxpb2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":895};
const content = `<path class="mrftxpb2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:mountains" {...props}></Icon>
