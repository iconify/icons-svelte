<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jg-1y-bay.css';
import '../../css/x/xszw9heki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jg-1y-bay"/><path class="xszw9heki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:file-copy-filled" {...props}></Icon>
