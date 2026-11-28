<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_ci9bxid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u_ci9bxid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:heart-minus" {...props}></Icon>
