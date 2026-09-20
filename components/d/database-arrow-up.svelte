<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqevs9bun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yqevs9bun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:database-arrow-up" {...props}></Icon>
