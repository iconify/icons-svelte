<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c35jjbcci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c35jjbcci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:anticlockwise-2-line" {...props}></Icon>
