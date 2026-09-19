<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwcf03b8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jwcf03b8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:bcpt" {...props}></Icon>
