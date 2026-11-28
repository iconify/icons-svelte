<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzop4oy-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uzop4oy-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:cards" {...props}></Icon>
