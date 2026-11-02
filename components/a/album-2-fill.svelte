<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrx_7bb6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nrx_7bb6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:album-2-fill" {...props}></Icon>
