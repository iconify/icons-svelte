<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c53i_1bdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c53i_1bdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:footer" {...props}></Icon>
