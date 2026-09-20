<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2r_egrqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t2r_egrqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:bluetooth-b" {...props}></Icon>
