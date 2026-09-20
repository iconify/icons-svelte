<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxbnq1bpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxbnq1bpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:heart-hand-line" {...props}></Icon>
