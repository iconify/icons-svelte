<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fylc7j5wh.css';
import '../../css/r/rn0ksnpzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fylc7j5wh"/><path class="rn0ksnpzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:file-pen-filled" {...props}></Icon>
