<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5p75l_6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q5p75l_6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:local-print-shop" {...props}></Icon>
