<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfcbn9dsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gfcbn9dsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:github-2-fill" {...props}></Icon>
