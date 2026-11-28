<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5ey-hrqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r5ey-hrqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:cloudy" {...props}></Icon>
