<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cub4olbfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cub4olbfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:heading-2" {...props}></Icon>
