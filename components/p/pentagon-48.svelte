<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpbyx1ete.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qpbyx1ete"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pentagon-48" {...props}></Icon>
