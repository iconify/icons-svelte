<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqgunnogm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oqgunnogm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:arrow-with-circle-left" {...props}></Icon>
