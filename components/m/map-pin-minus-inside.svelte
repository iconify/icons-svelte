<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfvx0vbqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wfvx0vbqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:map-pin-minus-inside" {...props}></Icon>
