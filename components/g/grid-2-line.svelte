<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exdgbrjak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="exdgbrjak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:grid-2-line" {...props}></Icon>
