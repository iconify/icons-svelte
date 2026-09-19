<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocx9jvbhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ocx9jvbhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:infinity" {...props}></Icon>
