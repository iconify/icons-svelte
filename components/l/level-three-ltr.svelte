<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_4aq0bli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x_4aq0bli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:level-three-ltr" {...props}></Icon>
