<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lj8lghwuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lj8lghwuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:air-balloon-line" {...props}></Icon>
