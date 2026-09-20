<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxkb7-xri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qxkb7-xri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:elevation-rise" {...props}></Icon>
