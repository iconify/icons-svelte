<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4cfp6b3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m4cfp6b3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:globe-model" {...props}></Icon>
