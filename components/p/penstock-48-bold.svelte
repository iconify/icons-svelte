<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-uyp2b0j.css';
import '../../css/q/qgl4r9bnu.css';
import '../../css/y/yf83rla5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="u-uyp2b0j"/><path class="qgl4r9bnu"/><path class="yf83rla5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:penstock-48-bold" {...props}></Icon>
