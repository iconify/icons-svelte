<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xz2gqrxrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xz2gqrxrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:base-station-2-line" {...props}></Icon>
