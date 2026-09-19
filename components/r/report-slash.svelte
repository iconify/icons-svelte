<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i73n831_u.css';
import '../../css/x/xl9hzbxpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i73n831_u"/><path class="xl9hzbxpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:report-slash" {...props}></Icon>
