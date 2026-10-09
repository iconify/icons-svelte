<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfchylgou.css';
import '../../css/a/aa6prfb-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gfchylgou"/><path class="aa6prfb-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:prism-48-bold" {...props}></Icon>
