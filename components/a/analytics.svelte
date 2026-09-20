<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxh_o_bia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxh_o_bia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:analytics" {...props}></Icon>
