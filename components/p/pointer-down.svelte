<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8h8dllmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="b8h8dllmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:pointer-down" {...props}></Icon>
