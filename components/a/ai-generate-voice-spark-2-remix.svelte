<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5gcds8nh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u5gcds8nh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:ai-generate-voice-spark-2-remix" {...props}></Icon>
