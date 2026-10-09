<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jj1y5cbbe.css';
import '../../css/u/uh_4a6zja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jj1y5cbbe"/><path class="uh_4a6zja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rego-certificate-48-bold" {...props}></Icon>
