<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uw60ip09k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uw60ip09k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:home-heart" {...props}></Icon>
