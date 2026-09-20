<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifvsw0btg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ifvsw0btg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:exit-line" {...props}></Icon>
