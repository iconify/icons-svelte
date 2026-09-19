<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ix75i-bma.css';
import '../../css/m/m5m_kacnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ix75i-bma"/><path class="m5m_kacnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-calendar-event" {...props}></Icon>
