<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdyaxkb1l.css';
import '../../css/e/e3qz-bbmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kdyaxkb1l"/><path class="e3qz-bbmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-left-to-line-48" {...props}></Icon>
