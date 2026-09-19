<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0td-222v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="y0td-222v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:briefcase" {...props}></Icon>
