<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eowd5-4tk.css';
import '../../css/k/kc1ovsb_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eowd5-4tk"/><path class="kc1ovsb_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:list-check-line" {...props}></Icon>
