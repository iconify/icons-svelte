<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zx61w1b0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zx61w1b0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:leaf-line" {...props}></Icon>
