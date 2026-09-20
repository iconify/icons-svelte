<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3ii_fjym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p3ii_fjym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:folo" {...props}></Icon>
