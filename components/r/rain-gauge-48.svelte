<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzojfwbzi.css';
import '../../css/x/xym1wwbma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uzojfwbzi"/><path class="xym1wwbma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rain-gauge-48" {...props}></Icon>
