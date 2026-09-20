<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_91e6x2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m_91e6x2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:filter-plus-outline" {...props}></Icon>
