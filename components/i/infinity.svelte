<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9ucdabdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p9ucdabdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:infinity" {...props}></Icon>
