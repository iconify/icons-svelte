<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omst-ztto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="omst-ztto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:plus-circled" {...props}></Icon>
