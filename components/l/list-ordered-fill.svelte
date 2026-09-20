<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtn8ih8gz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dtn8ih8gz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:list-ordered-fill" {...props}></Icon>
