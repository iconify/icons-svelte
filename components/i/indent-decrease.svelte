<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ze8ppqcua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="ze8ppqcua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:indent-decrease" {...props}></Icon>
