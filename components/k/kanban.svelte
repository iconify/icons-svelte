<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjhe4x-cj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xjhe4x-cj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:kanban" {...props}></Icon>
