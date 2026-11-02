<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4pq_6d1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y4pq_6d1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:columns-2-fill" {...props}></Icon>
