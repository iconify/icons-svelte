<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqt_hn3mb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cqt_hn3mb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:memory-stick-line" {...props}></Icon>
