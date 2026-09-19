<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iq1zrmmbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="iq1zrmmbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:info" {...props}></Icon>
