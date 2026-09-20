<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydmyssbmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ydmyssbmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:human-ski-water" {...props}></Icon>
