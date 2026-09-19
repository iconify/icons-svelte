<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esxpy3bry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":916};
const content = `<path class="esxpy3bry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:observatory" {...props}></Icon>
