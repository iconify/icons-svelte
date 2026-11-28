<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ee66iud3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ee66iud3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:circle-7" {...props}></Icon>
