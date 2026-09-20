<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fo5l02dsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fo5l02dsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rabbit-fill" {...props}></Icon>
