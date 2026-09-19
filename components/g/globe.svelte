<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ug_jkob0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ug_jkob0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:globe" {...props}></Icon>
