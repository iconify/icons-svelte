<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rq7qwfd8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rq7qwfd8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-bar-down" {...props}></Icon>
