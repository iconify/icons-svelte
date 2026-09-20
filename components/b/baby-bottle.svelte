<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avo0fx4sb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="avo0fx4sb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:baby-bottle" {...props}></Icon>
