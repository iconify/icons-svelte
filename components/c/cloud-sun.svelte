<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6qou888f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="m6qou888f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:cloud-sun" {...props}></Icon>
