<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lt3g05bav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="lt3g05bav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:colon" {...props}></Icon>
