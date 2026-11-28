<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eh5omfb9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eh5omfb9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:map-pin-x" {...props}></Icon>
