<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o11i93z8m.css';
import '../../css/x/xtw1k2b2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o11i93z8m"/><path class="xtw1k2b2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:conflux" {...props}></Icon>
