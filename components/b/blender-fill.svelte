<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjr2ylb9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vjr2ylb9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:blender-fill" {...props}></Icon>
