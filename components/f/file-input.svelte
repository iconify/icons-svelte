<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2kvgvbvc.css';
import '../../css/v/vk4yonzaw.css';
import '../../css/p/p1kbumysc.css';
import '../../css/o/ozl2zbbuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="vk4yonzaw"/><path class="p1kbumysc"/><path class="ozl2zbbuw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:file-input" {...props}></Icon>
