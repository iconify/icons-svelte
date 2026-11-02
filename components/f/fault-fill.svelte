<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tscstsbri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tscstsbri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fault-fill" {...props}></Icon>
