<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u806g0bsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u806g0bsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:medical-house-solid" {...props}></Icon>
