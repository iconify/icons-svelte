<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arptzobve.css';
import '../../css/x/xomdi8b2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="arptzobve"/><path class="xomdi8b2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:poland" {...props}></Icon>
