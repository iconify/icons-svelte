<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_r0tjbwq.css';
import '../../css/d/duhh5kbbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u_r0tjbwq"/><path clip-rule="evenodd" class="duhh5kbbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:bar-chart-dollar" {...props}></Icon>
