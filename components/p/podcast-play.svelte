<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exwoq60zg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="exwoq60zg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:podcast-play" {...props}></Icon>
