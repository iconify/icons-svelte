<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvv1ubwib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rvv1ubwib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:blocks-and-arrows" {...props}></Icon>
