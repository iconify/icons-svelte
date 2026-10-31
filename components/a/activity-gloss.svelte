<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-h14rbee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d-h14rbee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:activity-gloss" {...props}></Icon>
