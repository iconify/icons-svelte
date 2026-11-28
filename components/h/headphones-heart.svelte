<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vx65m281l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vx65m281l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:headphones-heart" {...props}></Icon>
