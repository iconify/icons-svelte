<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9-giub2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q9-giub2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:circle-dashed-duo" {...props}></Icon>
