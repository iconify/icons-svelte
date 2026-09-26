<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpb40w-0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qpb40w-0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:drain" {...props}></Icon>
