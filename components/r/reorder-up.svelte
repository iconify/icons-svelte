<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8as2hbtw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h8as2hbtw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:reorder-up" {...props}></Icon>
