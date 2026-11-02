<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xups6zouc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xups6zouc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mic-off-line" {...props}></Icon>
