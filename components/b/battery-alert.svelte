<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azn8int9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":216,"height":432};
const content = `<path class="azn8int9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:battery-alert" {...props}></Icon>
