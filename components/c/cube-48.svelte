<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kp2u-9b8d.css';
import '../../css/j/jznb33btn.css';
import '../../css/v/v30al6b2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kp2u-9b8d"/><path class="jznb33btn"/><path class="v30al6b2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cube-48" {...props}></Icon>
