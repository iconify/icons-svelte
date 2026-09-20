<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1ignbsnl.css';
import '../../css/g/g0qglybal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p1ignbsnl"/><path class="g0qglybal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:business-pearl-bold" {...props}></Icon>
