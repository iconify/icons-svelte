<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/as-_9328c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="as-_9328c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:line-style" {...props}></Icon>
