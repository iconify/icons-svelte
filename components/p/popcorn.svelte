<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymr-83eum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ymr-83eum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:popcorn" {...props}></Icon>
