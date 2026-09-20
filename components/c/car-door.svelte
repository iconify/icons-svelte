<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vynnw1j_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vynnw1j_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:car-door" {...props}></Icon>
