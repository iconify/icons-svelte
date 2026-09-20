<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igv29e4iv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":120,"height":60};
const content = `<path class="igv29e4iv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:alpha-vantage" {...props}></Icon>
