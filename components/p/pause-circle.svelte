<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6tkq1bcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n6tkq1bcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:pause-circle" {...props}></Icon>
