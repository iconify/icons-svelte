<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h21e71bvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="h21e71bvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:device" {...props}></Icon>
