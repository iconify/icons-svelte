<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vsh9etb_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vsh9etb_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:cloud-question" {...props}></Icon>
