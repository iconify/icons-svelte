<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xspafrbjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xspafrbjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:cellular-sharp" {...props}></Icon>
