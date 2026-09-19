<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlvagnwwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="vlvagnwwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:plus-box" {...props}></Icon>
