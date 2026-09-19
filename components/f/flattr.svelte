<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvj8svzab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rvj8svzab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:flattr" {...props}></Icon>
