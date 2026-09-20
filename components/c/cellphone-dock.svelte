<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8dcblb-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z8dcblb-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cellphone-dock" {...props}></Icon>
