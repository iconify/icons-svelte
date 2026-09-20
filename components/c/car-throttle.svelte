<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfo358bge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vfo358bge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:car-throttle" {...props}></Icon>
