<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z184dzb_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z184dzb_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:checks-fill" {...props}></Icon>
