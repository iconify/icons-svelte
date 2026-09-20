<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6zxn_qsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p6zxn_qsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:docment-line" {...props}></Icon>
