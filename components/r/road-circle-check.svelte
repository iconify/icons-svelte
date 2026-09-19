<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bag_e0a9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="bag_e0a9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:road-circle-check" {...props}></Icon>
