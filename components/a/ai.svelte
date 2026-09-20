<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_q-aje7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r_q-aje7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:ai" {...props}></Icon>
