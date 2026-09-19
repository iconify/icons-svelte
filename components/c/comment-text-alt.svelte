<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7ktuhjxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="x7ktuhjxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:comment-text-alt" {...props}></Icon>
