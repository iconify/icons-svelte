<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7-yjp58x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p7-yjp58x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:corner-up-left-line" {...props}></Icon>
