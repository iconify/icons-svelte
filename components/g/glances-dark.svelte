<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxbapv4lj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rxbapv4lj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:glances-dark" {...props}></Icon>
