<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lctp2pzbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lctp2pzbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-5-fill" {...props}></Icon>
