<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vw0d3xbjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vw0d3xbjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:human-resources-rating-woman-bold" {...props}></Icon>
