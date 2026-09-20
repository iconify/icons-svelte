<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc-fz3p4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bc-fz3p4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:prescription" {...props}></Icon>
