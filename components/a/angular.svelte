<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogjvrk1uq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ogjvrk1uq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:angular" {...props}></Icon>
