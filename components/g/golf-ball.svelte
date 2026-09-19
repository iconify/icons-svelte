<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2bivto0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":416,"height":512};
const content = `<path class="k2bivto0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:golf-ball" {...props}></Icon>
