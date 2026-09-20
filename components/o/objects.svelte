<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l893odb4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l893odb4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:objects" {...props}></Icon>
