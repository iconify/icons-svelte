<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytvy4rbcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ytvy4rbcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fullscreen-exit-2-fill" {...props}></Icon>
