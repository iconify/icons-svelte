<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m70158i_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m70158i_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:brush-3-fill" {...props}></Icon>
