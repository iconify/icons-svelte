<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vso738k7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vso738k7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:gallery-horizontal-end-line" {...props}></Icon>
