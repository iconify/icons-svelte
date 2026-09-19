<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wummjl_3r.css';
import '../../css/q/qpjvcje9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wummjl_3r"/><path class="qpjvcje9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:package-text-analysis" {...props}></Icon>
