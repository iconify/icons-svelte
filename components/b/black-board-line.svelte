<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4za2abrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m4za2abrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:black-board-line" {...props}></Icon>
