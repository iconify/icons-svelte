<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hucfk3b8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hucfk3b8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:lightbulb-night-outline" {...props}></Icon>
