<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypov33b7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ypov33b7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:inbox" {...props}></Icon>
