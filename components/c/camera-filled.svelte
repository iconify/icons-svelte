<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ef6k_cc-g.css';
import '../../css/t/t7his9f7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ef6k_cc-g"/><path class="t7his9f7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:camera-filled" {...props}></Icon>
