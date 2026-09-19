<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hs7-t7byx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="hs7-t7byx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:file-font" {...props}></Icon>
