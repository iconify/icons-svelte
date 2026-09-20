<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4kogebfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k4kogebfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:picture-in-picture-exit-fill" {...props}></Icon>
