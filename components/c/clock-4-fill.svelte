<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6bb_nbyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t6bb_nbyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:clock-4-fill" {...props}></Icon>
