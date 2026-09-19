<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfnuo7ojb.css';
import '../../css/t/tmkl2dpkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bfnuo7ojb"/><path class="tmkl2dpkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:lightbulb-off-solid" {...props}></Icon>
