<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rc1dgrbmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rc1dgrbmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:close-thin" {...props}></Icon>
