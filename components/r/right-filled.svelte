<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pyqc8-t6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pyqc8-t6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:right-filled" {...props}></Icon>
