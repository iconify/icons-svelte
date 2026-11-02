<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nt5u8-bsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nt5u8-bsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:clock-4-line" {...props}></Icon>
