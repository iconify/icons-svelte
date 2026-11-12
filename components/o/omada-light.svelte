<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvuee1bgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jvuee1bgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:omada-light" {...props}></Icon>
