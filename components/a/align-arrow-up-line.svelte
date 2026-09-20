<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dly37_bzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dly37_bzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-arrow-up-line" {...props}></Icon>
