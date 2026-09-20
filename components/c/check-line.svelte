<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhy5-hkxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jhy5-hkxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:check-line" {...props}></Icon>
