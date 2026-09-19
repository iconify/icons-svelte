<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r97-9822y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r97-9822y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:download" {...props}></Icon>
