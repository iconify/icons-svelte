<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1gjrv-xu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="s1gjrv-xu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:link-stroke-12" {...props}></Icon>
