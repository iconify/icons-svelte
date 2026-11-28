<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/sr1vlw5wv.css';
import '../../css/y/ygn003bwe.css';
import '../../css/t/tgob03bne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="sr1vlw5wv"/><path class="ygn003bwe"/><path class="tgob03bne"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-down-through-line" {...props}></Icon>
