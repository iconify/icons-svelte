<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zp8vudhak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zp8vudhak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:error-prompt" {...props}></Icon>
