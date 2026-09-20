<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwv0ewblt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qwv0ewblt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:horoscope-sagittarius" {...props}></Icon>
