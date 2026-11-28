<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1vdp1oey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u1vdp1oey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:corner-up-right-solid" {...props}></Icon>
