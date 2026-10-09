<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-eh9wb_p.css';
import '../../css/q/q3uapjb3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="u-eh9wb_p"/><path class="q3uapjb3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pool-48" {...props}></Icon>
