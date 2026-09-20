<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ms2x3t45m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ms2x3t45m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:middle-finger-fill" {...props}></Icon>
