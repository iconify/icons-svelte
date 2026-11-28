<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dp6q3mb9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dp6q3mb9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:file-video" {...props}></Icon>
