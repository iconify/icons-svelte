<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f382eabdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f382eabdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:file-download" {...props}></Icon>
