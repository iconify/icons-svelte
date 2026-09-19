<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ua-9c7bmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ua-9c7bmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:area-graph" {...props}></Icon>
