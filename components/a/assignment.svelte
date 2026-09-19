<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecy_mvlqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":432};
const content = `<path class="ecy_mvlqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:assignment" {...props}></Icon>
