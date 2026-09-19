<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k25y2fb7n.css';
import '../../css/w/w0h6xabmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b k25y2fb7n"/><path class="b w0h6xabmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:lottie-lab" {...props}></Icon>
