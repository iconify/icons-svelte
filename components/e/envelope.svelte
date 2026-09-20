<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqdv3t5-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qqdv3t5-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:envelope" {...props}></Icon>
