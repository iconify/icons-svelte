<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvku5ny2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rvku5ny2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:ngc-outline" {...props}></Icon>
