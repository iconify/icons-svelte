<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-cbzraid.css';
import '../../css/f/f3r88-jzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-cbzraid"/><path clip-rule="evenodd" class="f3r88-jzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:point-on-map-bold-duotone" {...props}></Icon>
