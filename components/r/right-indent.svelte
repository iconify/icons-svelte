<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4_7_6h1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s4_7_6h1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:right-indent" {...props}></Icon>
