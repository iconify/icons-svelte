<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxg6ho_0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uxg6ho_0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:moocup-light" {...props}></Icon>
