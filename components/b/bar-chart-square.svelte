<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/baahp-79z.css';
import '../../css/h/h55kfl3ha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="baahp-79z"/><path class="h55kfl3ha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bar-chart-square" {...props}></Icon>
