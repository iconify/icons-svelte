<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpzfc96fx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fpzfc96fx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-upload-fill" {...props}></Icon>
