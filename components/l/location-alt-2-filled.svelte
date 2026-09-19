<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixo8itb4g.css';
import '../../css/k/k0mq39bwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixo8itb4g"/><path class="k0mq39bwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:location-alt-2-filled" {...props}></Icon>
