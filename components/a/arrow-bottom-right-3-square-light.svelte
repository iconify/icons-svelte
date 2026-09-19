<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kn6nebcdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kn6nebcdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-bottom-right-3-square-light" {...props}></Icon>
