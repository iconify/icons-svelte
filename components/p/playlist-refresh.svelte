<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nc1rpebar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nc1rpebar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:playlist-refresh" {...props}></Icon>
