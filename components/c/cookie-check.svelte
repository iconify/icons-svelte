<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1ea-052t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r1ea-052t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:cookie-check" {...props}></Icon>
