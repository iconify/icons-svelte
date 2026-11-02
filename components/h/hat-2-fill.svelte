<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ib4amlbfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ib4amlbfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hat-2-fill" {...props}></Icon>
