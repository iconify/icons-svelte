<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qam1p736p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qam1p736p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:follow-line" {...props}></Icon>
