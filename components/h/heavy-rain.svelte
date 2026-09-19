<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwhkn3x3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kwhkn3x3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:heavy-rain" {...props}></Icon>
