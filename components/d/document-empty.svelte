<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-71yu7tl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a-71yu7tl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:document-empty" {...props}></Icon>
