<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oaw47gb6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oaw47gb6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:megaphone-check" {...props}></Icon>
