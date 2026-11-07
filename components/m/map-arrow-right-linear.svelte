<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_-k83bxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m_-k83bxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:map-arrow-right-linear" {...props}></Icon>
