<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3s83n2ce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y3s83n2ce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:anyappstart-light" {...props}></Icon>
