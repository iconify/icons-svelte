<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bl17533zy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bl17533zy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chrome-line" {...props}></Icon>
