<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kq5oa0pvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kq5oa0pvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:equal-approximately-line" {...props}></Icon>
