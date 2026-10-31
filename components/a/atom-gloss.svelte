<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jb0g46b6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jb0g46b6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:atom-gloss" {...props}></Icon>
