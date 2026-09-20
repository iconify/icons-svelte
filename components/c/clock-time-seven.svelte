<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nabu3x5no.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nabu3x5no"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clock-time-seven" {...props}></Icon>
