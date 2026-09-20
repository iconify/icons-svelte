<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dbkf7dqvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dbkf7dqvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:monitor-lock" {...props}></Icon>
