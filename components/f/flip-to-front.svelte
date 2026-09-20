<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kych3mbnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kych3mbnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:flip-to-front" {...props}></Icon>
