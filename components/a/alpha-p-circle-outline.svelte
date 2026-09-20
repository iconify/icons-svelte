<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1hq75p3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d1hq75p3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alpha-p-circle-outline" {...props}></Icon>
