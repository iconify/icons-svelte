<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqq645bio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vqq645bio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:goto-outline" {...props}></Icon>
