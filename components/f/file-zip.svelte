<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xy7g4tbnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xy7g4tbnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:file-zip" {...props}></Icon>
