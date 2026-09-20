<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7lvpblq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sv7lvpblq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-ipad-horizontal-cog" {...props}></Icon>
