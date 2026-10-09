<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6c7rh25t.css';
import '../../css/r/roygfgbrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="a6c7rh25t"/><path class="roygfgbrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:coupling-48" {...props}></Icon>
