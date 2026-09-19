<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypx0rvnvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ypx0rvnvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:golo" {...props}></Icon>
