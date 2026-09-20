<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ity3c0bdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ity3c0bdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:ai-generate-voice-spark-2-solid" {...props}></Icon>
