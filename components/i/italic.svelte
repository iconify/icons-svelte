<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nk0v84bdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="nk0v84bdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:italic" {...props}></Icon>
