<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylobwvhsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1728,"height":1280};
const content = `<path class="ylobwvhsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:long-arrow-left" {...props}></Icon>
