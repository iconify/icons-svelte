<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kw0603bzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kw0603bzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bow-tie-line" {...props}></Icon>
