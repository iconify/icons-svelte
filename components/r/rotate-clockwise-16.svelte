<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-_punbps.css';
import '../../css/q/q8b3x8beh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="h-_punbps"/><path class="q8b3x8beh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:rotate-clockwise-16" {...props}></Icon>
