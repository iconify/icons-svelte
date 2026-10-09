<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ao6abl51c.css';
import '../../css/x/xn11esbqe.css';
import '../../css/u/umr1ykbuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ao6abl51c"/><path class="xn11esbqe"/><path class="umr1ykbuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:certificate-48" {...props}></Icon>
