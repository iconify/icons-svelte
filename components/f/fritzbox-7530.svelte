<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjp8o5b5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xjp8o5b5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:fritzbox-7530" {...props}></Icon>
