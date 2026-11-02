<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlf0m3-1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qlf0m3-1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:park-fill" {...props}></Icon>
