<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in2zqfbio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="in2zqfbio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:envelope" {...props}></Icon>
