<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcy2s53wi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="zcy2s53wi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:chevron-compact-down" {...props}></Icon>
