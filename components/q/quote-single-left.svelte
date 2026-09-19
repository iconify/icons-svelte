<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2bs58bvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j2bs58bvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:quote-single-left" {...props}></Icon>
