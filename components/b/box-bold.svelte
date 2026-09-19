<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2817obpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m2817obpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:box-bold" {...props}></Icon>
