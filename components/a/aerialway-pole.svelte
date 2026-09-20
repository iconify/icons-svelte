<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3uj6cz7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="l3uj6cz7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:aerialway-pole" {...props}></Icon>
