<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2yfoxp2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="m2yfoxp2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:pilcrow-20-solid" {...props}></Icon>
