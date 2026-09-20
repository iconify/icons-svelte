<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsh3j-hwo.css';
import '../../css/o/oxl9k8wxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xsh3j-hwo"/><path class="oxl9k8wxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lumio" {...props}></Icon>
