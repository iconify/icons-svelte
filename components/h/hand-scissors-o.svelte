<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3h5st27g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1536};
const content = `<path class="k3h5st27g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:hand-scissors-o" {...props}></Icon>
