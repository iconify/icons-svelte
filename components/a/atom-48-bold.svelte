<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tptd5ygch.css';
import '../../css/i/iklw8pg9o.css';
import '../../css/r/r2a1kcczy.css';
import '../../css/b/b0a2wmopo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tptd5ygch"/><path class="iklw8pg9o"/><path class="r2a1kcczy"/><path class="b0a2wmopo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:atom-48-bold" {...props}></Icon>
