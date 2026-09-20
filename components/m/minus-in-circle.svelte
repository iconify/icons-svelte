<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxe03ccvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wxe03ccvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:minus-in-circle" {...props}></Icon>
