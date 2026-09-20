<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8a5w0b3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="t8a5w0b3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:oil-well" {...props}></Icon>
