<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpngxw3vl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kpngxw3vl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:circle-arrow-out-up-left-line" {...props}></Icon>
