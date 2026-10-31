<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7du0phez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r7du0phez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:code-bulk-round" {...props}></Icon>
