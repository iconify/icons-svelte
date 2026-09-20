<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/he7n4hb1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="he7n4hb1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:kite-line" {...props}></Icon>
