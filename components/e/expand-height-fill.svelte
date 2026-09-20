<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwc05acsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qwc05acsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:expand-height-fill" {...props}></Icon>
