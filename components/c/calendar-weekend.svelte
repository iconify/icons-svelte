<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mov6m_bbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mov6m_bbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:calendar-weekend" {...props}></Icon>
