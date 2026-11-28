<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_twdnb2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_twdnb2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:fishing-rod" {...props}></Icon>
