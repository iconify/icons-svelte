<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkoka4bop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wkoka4bop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrow-path-single-clockwise" {...props}></Icon>
