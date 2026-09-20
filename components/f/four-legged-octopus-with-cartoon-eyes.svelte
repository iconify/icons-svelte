<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/py1y6o2db.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="py1y6o2db"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:four-legged-octopus-with-cartoon-eyes" {...props}></Icon>
