<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9s_kubnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q9s_kubnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:key-2-line" {...props}></Icon>
