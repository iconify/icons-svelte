<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccx82wv1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ccx82wv1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fire-fill" {...props}></Icon>
