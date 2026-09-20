<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xoazjybag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":220,"height":220};
const content = `<path class="xoazjybag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:milanote-light" {...props}></Icon>
