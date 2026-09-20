<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4wdck6_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k4wdck6_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:image-check" {...props}></Icon>
