<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqy5knu7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="vqy5knu7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:eject" {...props}></Icon>
