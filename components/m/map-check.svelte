<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icuogwm2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="icuogwm2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:map-check" {...props}></Icon>
