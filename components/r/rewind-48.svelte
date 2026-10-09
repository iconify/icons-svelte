<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4n60ybfu.css';
import '../../css/e/e52uakbgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k4n60ybfu"/><path class="e52uakbgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rewind-48" {...props}></Icon>
