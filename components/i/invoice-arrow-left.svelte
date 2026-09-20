<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mu7m_8bkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mu7m_8bkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:invoice-arrow-left" {...props}></Icon>
