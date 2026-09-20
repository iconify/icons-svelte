<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkon9widq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vkon9widq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:hexagon-number-7-filled" {...props}></Icon>
