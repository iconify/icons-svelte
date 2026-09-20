<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kr8y-6-3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kr8y-6-3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:donut-fill" {...props}></Icon>
