<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbmcrcl1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gbmcrcl1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:link-round-linear" {...props}></Icon>
