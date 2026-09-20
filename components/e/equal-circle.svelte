<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yx-4nmbtx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yx-4nmbtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:equal-circle" {...props}></Icon>
