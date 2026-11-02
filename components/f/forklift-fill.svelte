<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xae4x2bpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xae4x2bpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:forklift-fill" {...props}></Icon>
