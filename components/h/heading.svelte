<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sr9t3tb3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sr9t3tb3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:heading" {...props}></Icon>
