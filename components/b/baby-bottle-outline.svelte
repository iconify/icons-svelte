<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hc2ot-beb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hc2ot-beb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:baby-bottle-outline" {...props}></Icon>
