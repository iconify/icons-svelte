<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ov26wzbtk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ov26wzbtk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:indoor-rowing-line" {...props}></Icon>
