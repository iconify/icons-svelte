<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5gu50boq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a5gu50boq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:database-hierarchy" {...props}></Icon>
