<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u64e3ubte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u64e3ubte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flag-triangle-left-line" {...props}></Icon>
