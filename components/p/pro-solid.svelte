<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwcd64bwj.css';
import '../../css/v/vezww5hdy.css';
import '../../css/i/ipwmjm2oi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lwcd64bwj"/><path class="vezww5hdy"/><path class="ipwmjm2oi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:pro-solid" {...props}></Icon>
