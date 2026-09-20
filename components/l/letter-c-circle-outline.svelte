<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rockq_psm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rockq_psm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:letter-c-circle-outline" {...props}></Icon>
