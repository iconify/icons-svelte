<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ceznk2bwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ceznk2bwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rewind-backward-15-line" {...props}></Icon>
