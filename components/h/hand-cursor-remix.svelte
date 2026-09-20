<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oljv3-_nv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="oljv3-_nv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:hand-cursor-remix" {...props}></Icon>
