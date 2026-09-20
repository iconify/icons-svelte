<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-m_vqxss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="s-m_vqxss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:music-note-2-flat" {...props}></Icon>
