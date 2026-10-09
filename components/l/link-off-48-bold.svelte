<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kf09_5bop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kf09_5bop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:link-off-48-bold" {...props}></Icon>
