<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljudbibqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ljudbibqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ai-face-circle-look-down-solid" {...props}></Icon>
