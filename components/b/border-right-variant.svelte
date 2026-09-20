<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gg35955pn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gg35955pn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:border-right-variant" {...props}></Icon>
