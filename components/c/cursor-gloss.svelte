<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfcunmbkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cfcunmbkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:cursor-gloss" {...props}></Icon>
