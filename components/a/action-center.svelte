<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnesecm2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="pnesecm2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:action-center" {...props}></Icon>
