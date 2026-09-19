<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5en5pmvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1026,"height":1025};
const content = `<path class="s5en5pmvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:medal" {...props}></Icon>
