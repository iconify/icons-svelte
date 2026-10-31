<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tl8-tdb0a.css';
import '../../css/l/l9cl-boot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="tl8-tdb0a"/><path class="l9cl-boot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:nigeria" {...props}></Icon>
