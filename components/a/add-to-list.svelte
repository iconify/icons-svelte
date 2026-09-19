<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sju3_vtms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sju3_vtms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:add-to-list" {...props}></Icon>
