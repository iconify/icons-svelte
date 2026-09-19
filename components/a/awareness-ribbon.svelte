<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3y1o4bjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f3y1o4bjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:awareness-ribbon" {...props}></Icon>
