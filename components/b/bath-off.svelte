<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds20tl5cj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ds20tl5cj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bath-off" {...props}></Icon>
