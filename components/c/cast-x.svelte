<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhvdx6bgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mhvdx6bgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:cast-x" {...props}></Icon>
