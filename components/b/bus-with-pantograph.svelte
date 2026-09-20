<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iucqgg8hm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="iucqgg8hm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bus-with-pantograph" {...props}></Icon>
