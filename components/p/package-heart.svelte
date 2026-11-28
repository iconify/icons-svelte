<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wt6ajr72g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wt6ajr72g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:package-heart" {...props}></Icon>
