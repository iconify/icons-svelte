<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uabn4_hhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uabn4_hhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pig-fill" {...props}></Icon>
