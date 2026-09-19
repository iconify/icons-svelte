<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w91eb_b8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="w91eb_b8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:house-chimney-crack" {...props}></Icon>
