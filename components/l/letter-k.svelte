<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-j-jjbdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-j-jjbdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:letter-k" {...props}></Icon>
