<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l73ftcc0i.css';
import '../../css/v/vimw34l9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l73ftcc0i"/><path class="vimw34l9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-charging-48" {...props}></Icon>
