<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5f5335vk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="x5f5335vk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:dot-octagon" {...props}></Icon>
