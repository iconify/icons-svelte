<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7to8vrmi.css';
import '../../css/r/r49wnackk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="a7to8vrmi"/><path class="r49wnackk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:page-break-1" {...props}></Icon>
