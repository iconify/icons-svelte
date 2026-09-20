<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qet681b4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qet681b4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:fingerprint-2-line" {...props}></Icon>
