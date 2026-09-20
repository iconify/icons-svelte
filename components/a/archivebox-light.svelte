<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fd7_0ccbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fd7_0ccbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:archivebox-light" {...props}></Icon>
