<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rf2iqfbae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rf2iqfbae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-horizontal-distribute-center-line" {...props}></Icon>
