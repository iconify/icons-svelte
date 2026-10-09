<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-kp5908v.css';
import '../../css/x/xhbmkr9uj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l-kp5908v"/><path class="xhbmkr9uj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-pack-48" {...props}></Icon>
