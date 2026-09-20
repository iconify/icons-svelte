<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gr0d2pbyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gr0d2pbyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:info-board" {...props}></Icon>
