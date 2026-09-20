<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h__abybcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h__abybcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-drop-down-line" {...props}></Icon>
