<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_c5285vz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m_c5285vz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pig-variant-outline" {...props}></Icon>
