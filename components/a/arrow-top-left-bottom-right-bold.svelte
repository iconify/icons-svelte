<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e31ik5bcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e31ik5bcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-top-left-bottom-right-bold" {...props}></Icon>
