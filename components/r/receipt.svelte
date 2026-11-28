<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2psfcczh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d2psfcczh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:receipt" {...props}></Icon>
