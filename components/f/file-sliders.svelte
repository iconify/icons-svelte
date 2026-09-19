<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sp2-p1nqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sp2-p1nqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:file-sliders" {...props}></Icon>
