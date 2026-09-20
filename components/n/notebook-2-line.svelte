<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8q64_3nk.css';
import '../../css/k/kuvr68irh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s8q64_3nk"/><path class="kuvr68irh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:notebook-2-line" {...props}></Icon>
