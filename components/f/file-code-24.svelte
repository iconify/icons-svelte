<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iy6j6obsd.css';
import '../../css/e/e7yp3qfxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iy6j6obsd"/><path class="e7yp3qfxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:file-code-24" {...props}></Icon>
