<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/np_e4lx1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="np_e4lx1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:letterboxd-light" {...props}></Icon>
