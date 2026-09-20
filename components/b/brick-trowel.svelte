<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxmyoogdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qxmyoogdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:brick-trowel" {...props}></Icon>
