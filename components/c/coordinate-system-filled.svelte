<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgc1imbmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qgc1imbmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:coordinate-system-filled" {...props}></Icon>
