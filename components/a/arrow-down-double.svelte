<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rf-_y3b4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rf-_y3b4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:arrow-down-double" {...props}></Icon>
