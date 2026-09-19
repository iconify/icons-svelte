<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yejrxzajr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":416};
const content = `<path class="yejrxzajr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:github" {...props}></Icon>
