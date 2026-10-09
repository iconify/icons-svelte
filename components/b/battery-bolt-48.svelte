<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_v0l2tzx.css';
import '../../css/z/z3zho9lws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d_v0l2tzx"/><path class="z3zho9lws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-bolt-48" {...props}></Icon>
