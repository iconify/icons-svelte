<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jr-9tjbeb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jr-9tjbeb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:resize-arrow-expand-vertical-1" {...props}></Icon>
