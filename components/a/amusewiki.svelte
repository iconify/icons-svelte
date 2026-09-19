<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/logf-5bvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="logf-5bvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:amusewiki" {...props}></Icon>
