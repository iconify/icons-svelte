<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ruxg_8bkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ruxg_8bkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:redo" {...props}></Icon>
