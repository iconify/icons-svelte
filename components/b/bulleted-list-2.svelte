<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw_vg6b8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="rw_vg6b8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:bulleted-list-2" {...props}></Icon>
