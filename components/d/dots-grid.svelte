<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_g7-bncq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m_g7-bncq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:dots-grid" {...props}></Icon>
