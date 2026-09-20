<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oibh5crij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oibh5crij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:instacart" {...props}></Icon>
