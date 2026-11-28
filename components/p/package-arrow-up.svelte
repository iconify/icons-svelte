<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/io8g53b4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="io8g53b4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:package-arrow-up" {...props}></Icon>
