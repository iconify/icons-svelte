<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zt5bmx3ap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zt5bmx3ap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:cloud" {...props}></Icon>
