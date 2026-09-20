<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8-i4fffi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o8-i4fffi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:jetblue-airways-light" {...props}></Icon>
