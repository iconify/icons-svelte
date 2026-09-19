<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9eriqbnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b9eriqbnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:circle-plus" {...props}></Icon>
