<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/id6amw2pa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="id6amw2pa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:blind-tilt-open" {...props}></Icon>
