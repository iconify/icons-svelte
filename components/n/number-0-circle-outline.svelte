<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qy_hb70yo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qy_hb70yo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:number-0-circle-outline" {...props}></Icon>
