<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-7s7tbbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="s-7s7tbbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:minnesota" {...props}></Icon>
