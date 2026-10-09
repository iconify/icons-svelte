<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ryya2cmsp.css';
import '../../css/m/mqlcs9bpx.css';
import '../../css/f/f_n_iqb4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ryya2cmsp"/><path class="mqlcs9bpx"/><path class="f_n_iqb4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:log-in-48-bold" {...props}></Icon>
