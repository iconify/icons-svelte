<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxfhyr3rt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oxfhyr3rt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:plane-takeoff" {...props}></Icon>
