<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijnwu_bsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ijnwu_bsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:hop-off" {...props}></Icon>
