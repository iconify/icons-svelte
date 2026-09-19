<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y22f7pbxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="y22f7pbxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:circle-with-plus" {...props}></Icon>
