<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-3o2v47x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s-3o2v47x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:clipboard-copy-line" {...props}></Icon>
