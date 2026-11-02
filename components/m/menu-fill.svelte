<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hez1ldp1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hez1ldp1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:menu-fill" {...props}></Icon>
