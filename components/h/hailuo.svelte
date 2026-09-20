<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhln_6f7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mhln_6f7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:hailuo" {...props}></Icon>
