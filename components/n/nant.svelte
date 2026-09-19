<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lo2nb0bvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lo2nb0bvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:nant" {...props}></Icon>
