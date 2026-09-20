<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnckoc04l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vnckoc04l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:car-electric" {...props}></Icon>
