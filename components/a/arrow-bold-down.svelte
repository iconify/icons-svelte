<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xja2x8adm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xja2x8adm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:arrow-bold-down" {...props}></Icon>
