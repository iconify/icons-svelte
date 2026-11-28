<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw1drz2ie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rw1drz2ie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:fish-heart" {...props}></Icon>
