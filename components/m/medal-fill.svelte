<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shaz69b3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="shaz69b3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:medal-fill" {...props}></Icon>
