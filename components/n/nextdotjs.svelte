<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipn624ygs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ipn624ygs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:nextdotjs" {...props}></Icon>
