<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pl4nvkpwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pl4nvkpwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:aqara-h2-switch" {...props}></Icon>
