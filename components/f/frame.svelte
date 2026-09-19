<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkwhx1bhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pkwhx1bhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:frame" {...props}></Icon>
