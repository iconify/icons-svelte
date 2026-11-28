<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v44wws-gq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v44wws-gq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:campfire-check" {...props}></Icon>
