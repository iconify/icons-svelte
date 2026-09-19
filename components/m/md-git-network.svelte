<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9z1e5gbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w9z1e5gbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-git-network" {...props}></Icon>
