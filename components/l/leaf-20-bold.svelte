<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvpxvsbif.css';
import '../../css/x/xph283bpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qvpxvsbif"/><path class="xph283bpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:leaf-20-bold" {...props}></Icon>
