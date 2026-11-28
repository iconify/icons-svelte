<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_x43ob0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_x43ob0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:home-gear" {...props}></Icon>
