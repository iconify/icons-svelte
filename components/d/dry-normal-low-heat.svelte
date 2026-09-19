<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwq6y7vmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kwq6y7vmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:dry-normal-low-heat" {...props}></Icon>
