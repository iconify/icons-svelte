<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xptd2s8fn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xptd2s8fn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:letter-spacing-line" {...props}></Icon>
