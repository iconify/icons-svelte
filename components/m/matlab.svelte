<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t54jjfbdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t54jjfbdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:matlab" {...props}></Icon>
