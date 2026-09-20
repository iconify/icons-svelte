<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9_1p1ist.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j9_1p1ist"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:airport" {...props}></Icon>
