<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yawx-mb9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yawx-mb9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:radio-line" {...props}></Icon>
