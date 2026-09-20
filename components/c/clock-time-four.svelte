<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_qhvzbiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_qhvzbiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clock-time-four" {...props}></Icon>
