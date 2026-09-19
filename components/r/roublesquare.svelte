<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dy_iepb2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="dy_iepb2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:roublesquare" {...props}></Icon>
