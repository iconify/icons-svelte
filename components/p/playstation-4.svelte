<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zn7dk11sn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zn7dk11sn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:playstation-4" {...props}></Icon>
