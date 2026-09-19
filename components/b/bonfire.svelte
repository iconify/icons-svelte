<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/g8gy9vy8e.css';
import '../../css/w/w6otkg_un.css';
import '../../css/w/w2fbwab-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="g8gy9vy8e"/><path class="w6otkg_un"/><path class="w2fbwab-k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:bonfire" {...props}></Icon>
