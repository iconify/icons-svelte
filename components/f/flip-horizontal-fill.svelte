<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0sd4meja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m0sd4meja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flip-horizontal-fill" {...props}></Icon>
