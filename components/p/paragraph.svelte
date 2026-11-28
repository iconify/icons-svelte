<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w848w8bex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w848w8bex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:paragraph" {...props}></Icon>
