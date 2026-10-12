<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7d8ty_6p.css';
import '../../css/e/e8_qdzh7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l7d8ty_6p"/><path class="e8_qdzh7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bear-48" {...props}></Icon>
