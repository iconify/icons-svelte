<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m20rxt8mc.css';
import '../../css/p/pkcnx6ceq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m20rxt8mc"/><path class="pkcnx6ceq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:content-files-open-book" {...props}></Icon>
