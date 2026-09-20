<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rt14pkbne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rt14pkbne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:pushpin-line" {...props}></Icon>
