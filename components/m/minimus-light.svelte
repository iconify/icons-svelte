<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lg2jjbcjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lg2jjbcjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:minimus-light" {...props}></Icon>
