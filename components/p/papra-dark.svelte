<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myf161b0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="myf161b0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:papra-dark" {...props}></Icon>
