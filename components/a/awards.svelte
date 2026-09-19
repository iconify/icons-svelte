<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kniqe2b7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kniqe2b7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:awards" {...props}></Icon>
