<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i84m_g4-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i84m_g4-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:encryption-add-outline" {...props}></Icon>
