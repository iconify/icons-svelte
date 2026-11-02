<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xop6-hfiw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xop6-hfiw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:copy-x-line" {...props}></Icon>
