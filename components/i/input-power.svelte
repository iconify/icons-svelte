<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9xpmoajl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":384};
const content = `<path class="u9xpmoajl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:input-power" {...props}></Icon>
