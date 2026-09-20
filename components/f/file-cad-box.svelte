<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xloze9r4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xloze9r4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-cad-box" {...props}></Icon>
