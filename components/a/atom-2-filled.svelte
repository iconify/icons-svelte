<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/au9uxsvgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="au9uxsvgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:atom-2-filled" {...props}></Icon>
