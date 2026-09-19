<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6xg3bb7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="j6xg3bb7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:flat-brush" {...props}></Icon>
