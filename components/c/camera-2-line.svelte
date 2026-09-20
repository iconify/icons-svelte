<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_wl7cckw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m_wl7cckw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:camera-2-line" {...props}></Icon>
