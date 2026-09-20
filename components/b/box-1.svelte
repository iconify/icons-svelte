<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mh8lsuzqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mh8lsuzqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:box-1" {...props}></Icon>
