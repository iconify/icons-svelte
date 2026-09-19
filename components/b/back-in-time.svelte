<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofbr-bi5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ofbr-bi5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:back-in-time" {...props}></Icon>
