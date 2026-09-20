<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tsmw1fyuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tsmw1fyuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:rail-filled" {...props}></Icon>
