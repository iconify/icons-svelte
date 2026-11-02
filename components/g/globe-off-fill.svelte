<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yoc2j8l5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yoc2j8l5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:globe-off-fill" {...props}></Icon>
