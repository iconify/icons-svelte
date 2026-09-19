<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmfmj4yhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="tmfmj4yhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:check-circle-u" {...props}></Icon>
