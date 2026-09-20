<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfhjrtb2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lfhjrtb2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:box-3-fill" {...props}></Icon>
