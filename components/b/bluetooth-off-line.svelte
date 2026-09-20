<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkbu6xuoc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gkbu6xuoc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bluetooth-off-line" {...props}></Icon>
