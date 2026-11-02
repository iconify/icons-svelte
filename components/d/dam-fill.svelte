<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9p5-ofhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e9p5-ofhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dam-fill" {...props}></Icon>
