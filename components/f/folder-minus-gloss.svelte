<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbl3e5bcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jbl3e5bcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:folder-minus-gloss" {...props}></Icon>
