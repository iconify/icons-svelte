<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rg94oxbop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rg94oxbop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:power-socket-europe" {...props}></Icon>
