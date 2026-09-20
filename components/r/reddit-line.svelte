<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7hi9sbth.css';
import '../../css/u/ukauanbdu.css';
import '../../css/m/mrpd8lbxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j7hi9sbth"/><path class="ukauanbdu"/><path class="mrpd8lbxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:reddit-line" {...props}></Icon>
