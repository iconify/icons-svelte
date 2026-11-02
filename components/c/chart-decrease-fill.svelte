<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9c0taccq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c9c0taccq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-decrease-fill" {...props}></Icon>
