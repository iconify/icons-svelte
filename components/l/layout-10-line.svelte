<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dni6aie-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dni6aie-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-10-line" {...props}></Icon>
