<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyium1yvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dyium1yvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:flower-gloss" {...props}></Icon>
