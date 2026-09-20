<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pot-aq7pv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pot-aq7pv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:pause-hexagon" {...props}></Icon>
