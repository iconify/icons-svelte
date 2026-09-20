<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5vu71b7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s5vu71b7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:four-wheel-drive-fill" {...props}></Icon>
