<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akoc4mw1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="akoc4mw1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-flame" {...props}></Icon>
