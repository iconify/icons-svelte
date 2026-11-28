<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwoqftb6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gwoqftb6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:flower-heart" {...props}></Icon>
