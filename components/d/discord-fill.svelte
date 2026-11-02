<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xc2cfj1yx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xc2cfj1yx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:discord-fill" {...props}></Icon>
