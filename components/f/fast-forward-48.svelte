<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7fb6nbqg.css';
import '../../css/x/xn59nof8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s7fb6nbqg"/><path class="xn59nof8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fast-forward-48" {...props}></Icon>
