<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xt8_zhj7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xt8_zhj7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hex-key-48" {...props}></Icon>
