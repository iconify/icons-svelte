<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l610tobwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l610tobwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:edit-document" {...props}></Icon>
