<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unwy9u_3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="unwy9u_3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:map-star" {...props}></Icon>
