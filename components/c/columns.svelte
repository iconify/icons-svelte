<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hr2xlsbcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hr2xlsbcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:columns" {...props}></Icon>
