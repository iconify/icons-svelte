<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klfvsd2kq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="klfvsd2kq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ear-off-line" {...props}></Icon>
