<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wldnpcbhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="wldnpcbhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:black-left-double-triangle-with-vertical-bar" {...props}></Icon>
