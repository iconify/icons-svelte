<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1tm3acmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g1tm3acmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:linux-line" {...props}></Icon>
