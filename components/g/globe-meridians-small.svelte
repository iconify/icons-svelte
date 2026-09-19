<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rx5ddjbmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="rx5ddjbmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:globe-meridians-small" {...props}></Icon>
