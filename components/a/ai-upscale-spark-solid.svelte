<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/te3uvd3yt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="te3uvd3yt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:ai-upscale-spark-solid" {...props}></Icon>
