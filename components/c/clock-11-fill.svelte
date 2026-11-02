<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixho66wnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixho66wnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:clock-11-fill" {...props}></Icon>
