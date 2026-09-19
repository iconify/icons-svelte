<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd06uhenr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":512};
const content = `<path class="kd06uhenr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:dry-flat" {...props}></Icon>
