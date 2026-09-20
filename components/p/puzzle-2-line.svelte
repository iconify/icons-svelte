<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vd17pjb3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vd17pjb3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:puzzle-2-line" {...props}></Icon>
