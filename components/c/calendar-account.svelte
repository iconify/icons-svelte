<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtv4w57nz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dtv4w57nz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:calendar-account" {...props}></Icon>
