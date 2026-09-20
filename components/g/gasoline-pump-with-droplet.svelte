<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ju7wy1k8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ju7wy1k8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:gasoline-pump-with-droplet" {...props}></Icon>
