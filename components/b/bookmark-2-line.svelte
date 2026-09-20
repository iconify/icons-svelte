<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/py0wdzxsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="py0wdzxsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:bookmark-2-line" {...props}></Icon>
