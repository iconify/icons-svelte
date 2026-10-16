<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya_ke-i5o.css';
import '../../css/v/vliuxwelf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ya_ke-i5o"/><path class="vliuxwelf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:junction-box-48" {...props}></Icon>
