<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iud-r9o8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iud-r9o8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-up5" {...props}></Icon>
