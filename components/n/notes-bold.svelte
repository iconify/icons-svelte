<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0lgf8m_j.css';
import '../../css/v/vdullb4tr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q0lgf8m_j"/><path clip-rule="evenodd" class="vdullb4tr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:notes-bold" {...props}></Icon>
