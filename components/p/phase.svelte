<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/woz_0rcvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="woz_0rcvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:phase" {...props}></Icon>
