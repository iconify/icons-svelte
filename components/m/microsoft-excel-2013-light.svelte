<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d488w9blp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d488w9blp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-excel-2013-light" {...props}></Icon>
