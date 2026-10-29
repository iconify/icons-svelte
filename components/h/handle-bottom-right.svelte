<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhi6qobkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bhi6qobkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:handle-bottom-right" {...props}></Icon>
