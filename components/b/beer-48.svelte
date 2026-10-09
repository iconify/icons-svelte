<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bk86n9brf.css';
import '../../css/x/xn-ip-jci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bk86n9brf"/><path class="xn-ip-jci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:beer-48" {...props}></Icon>
