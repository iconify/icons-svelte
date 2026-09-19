<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4w4jbcyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s4w4jbcyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:cloud-circle-sharp" {...props}></Icon>
