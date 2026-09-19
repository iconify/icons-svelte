<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwmkq4b2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="hwmkq4b2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:mapbox" {...props}></Icon>
