<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzn2sjbas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gzn2sjbas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:app-window-fill" {...props}></Icon>
