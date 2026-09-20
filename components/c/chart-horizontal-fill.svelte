<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnzcnch8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pnzcnch8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-horizontal-fill" {...props}></Icon>
