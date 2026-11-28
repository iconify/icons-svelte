<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrfo_dk8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jrfo_dk8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:map-lock" {...props}></Icon>
