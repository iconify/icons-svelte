<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjr9atbcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rjr9atbcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:bowl-heart" {...props}></Icon>
