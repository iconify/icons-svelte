<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_9j0qbcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j_9j0qbcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:radiology-box-outline" {...props}></Icon>
