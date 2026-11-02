<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g728b8bwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g728b8bwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-locked-line" {...props}></Icon>
