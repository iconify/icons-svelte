<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8o03pl8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p8o03pl8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:guide-line" {...props}></Icon>
