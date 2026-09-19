<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8u5an_lr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="s8u5an_lr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:minus-circle" {...props}></Icon>
