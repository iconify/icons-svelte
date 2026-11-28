<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s72dk49og.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s72dk49og"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:monitor-alert" {...props}></Icon>
