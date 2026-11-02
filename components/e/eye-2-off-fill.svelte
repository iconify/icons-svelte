<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dw_js72hb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dw_js72hb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:eye-2-off-fill" {...props}></Icon>
