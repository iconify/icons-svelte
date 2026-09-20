<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fp09bcbvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fp09bcbvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:portrait" {...props}></Icon>
