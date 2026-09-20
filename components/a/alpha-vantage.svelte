<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0z73lbsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":120,"height":60};
const content = `<path class="h0z73lbsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:alpha-vantage" {...props}></Icon>
