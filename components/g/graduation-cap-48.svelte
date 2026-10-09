<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhjv-fbep.css';
import '../../css/h/hkvtvtm6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yhjv-fbep"/><path class="hkvtvtm6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:graduation-cap-48" {...props}></Icon>
