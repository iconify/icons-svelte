<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di953abef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="di953abef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:cpu-fill" {...props}></Icon>
