<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/geb8sxbml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="geb8sxbml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:outdoor-lamp" {...props}></Icon>
