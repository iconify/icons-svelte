<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q679esbud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q679esbud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:certificate-2-line" {...props}></Icon>
