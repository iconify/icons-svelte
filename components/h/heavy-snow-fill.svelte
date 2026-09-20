<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwer2dd0j.css';
import '../../css/o/oulisxbyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cwer2dd0j"/><path class="oulisxbyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:heavy-snow-fill" {...props}></Icon>
