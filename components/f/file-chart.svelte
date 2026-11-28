<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqd6ufbuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tqd6ufbuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:file-chart" {...props}></Icon>
