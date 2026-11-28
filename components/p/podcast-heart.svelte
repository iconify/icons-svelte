<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ei0zwbb5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ei0zwbb5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:podcast-heart" {...props}></Icon>
