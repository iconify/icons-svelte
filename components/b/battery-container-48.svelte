<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gl2z74b1y.css';
import '../../css/l/lv3t6tmyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gl2z74b1y"/><path class="lv3t6tmyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-container-48" {...props}></Icon>
