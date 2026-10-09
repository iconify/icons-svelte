<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1mc6lwbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="e1mc6lwbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:carbon-footprint-48" {...props}></Icon>
