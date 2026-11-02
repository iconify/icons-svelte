<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvsmmsb3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tvsmmsb3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:plus-fill" {...props}></Icon>
