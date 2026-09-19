<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylz3-15ku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ylz3-15ku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:kotlin" {...props}></Icon>
