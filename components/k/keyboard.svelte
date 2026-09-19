<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yoeptobrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yoeptobrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:keyboard" {...props}></Icon>
