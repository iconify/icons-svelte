<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jd0xs_bxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jd0xs_bxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:artboard-fill" {...props}></Icon>
