<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlmdb_b8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="rlmdb_b8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:open-in-new-window" {...props}></Icon>
