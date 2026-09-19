<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9z-xfbjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="v9z-xfbjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:pause-circle" {...props}></Icon>
