<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kres2h2xx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kres2h2xx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-forbid-line" {...props}></Icon>
