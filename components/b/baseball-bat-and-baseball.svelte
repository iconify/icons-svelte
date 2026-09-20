<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjbo7ppxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pjbo7ppxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:baseball-bat-and-baseball" {...props}></Icon>
