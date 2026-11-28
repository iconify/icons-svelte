<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0l_l8baz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i0l_l8baz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:globe-off" {...props}></Icon>
