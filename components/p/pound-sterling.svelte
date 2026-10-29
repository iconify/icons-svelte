<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owz3mac6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="owz3mac6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:pound-sterling" {...props}></Icon>
