<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pppgz_8mj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pppgz_8mj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:circle-chevron-left" {...props}></Icon>
