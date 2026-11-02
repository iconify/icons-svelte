<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g70hjacsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g70hjacsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-code-line" {...props}></Icon>
